<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eq3d8hulp.css';
import '../../css/i/izk0irbfh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="eq3d8hulp"/><path class="izk0irbfh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:arrow-reverse-fill-16" {...props}></Icon>
