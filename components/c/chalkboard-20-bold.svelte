<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rv8ehtyui.css';
import '../../css/a/afwi5ac4o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="rv8ehtyui"/><path class="afwi5ac4o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:chalkboard-20-bold" {...props}></Icon>
