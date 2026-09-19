<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bmn7ynbep.css';
import '../../css/y/yohhqnr3k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<circle class="bmn7ynbep"/><path class="yohhqnr3k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:fish" {...props}></Icon>
