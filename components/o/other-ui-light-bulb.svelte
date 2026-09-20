<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fvswe7bnc.css';
import '../../css/o/of3lo06ag.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="fvswe7bnc"/><path class="of3lo06ag"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-block:other-ui-light-bulb" {...props}></Icon>
