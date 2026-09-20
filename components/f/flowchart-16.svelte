<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ifnps92yy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="ifnps92yy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:flowchart-16" {...props}></Icon>
