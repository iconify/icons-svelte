<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lubufcyue.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="lubufcyue"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:cline" {...props}></Icon>
