<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rawf947wb.css';
import '../../css/b/baxfr6ous.css';
import '../../css/k/k4thwtkyl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="rawf947wb"/><path class="baxfr6ous"/><path class="k4thwtkyl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-pixel:content-files-favorite-book" {...props}></Icon>
