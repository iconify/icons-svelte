<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/ba_3tvb6x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="ba_3tvb6x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cib:orcid" {...props}></Icon>
