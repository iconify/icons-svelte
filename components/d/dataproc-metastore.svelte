<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y2aal61ds.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="y2aal61ds"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gcp:dataproc-metastore" {...props}></Icon>
