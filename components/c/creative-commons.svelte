<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jxlnqwbll.css';
import '../../css/o/ooafjrbnh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jxlnqwbll"/><path class="ooafjrbnh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixel:creative-commons" {...props}></Icon>
