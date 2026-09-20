<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g8-uw-btt.css';
import '../../css/t/tmcxzhbqx.css';
import '../../css/c/c3ivfk8mr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="g8-uw-btt"/><path class="tmcxzhbqx"/><path class="c3ivfk8mr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-block:other-ui-target" {...props}></Icon>
