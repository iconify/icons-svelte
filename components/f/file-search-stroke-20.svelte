<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yfwdc41th.css';
import '../../css/l/lci61mkfz.css';
import '../../css/a/a8kb4gb9t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="yfwdc41th"/><path class="lci61mkfz"/><path class="a8kb4gb9t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:file-search-stroke-20" {...props}></Icon>
