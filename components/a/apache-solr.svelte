<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cj9rtizot.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cj9rtizot"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:apache-solr" {...props}></Icon>
