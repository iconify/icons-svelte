<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n1lsf0bnc.css';
import '../../css/s/s3fvc1qen.css';
import '../../css/k/k5darrm3j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<g class="n1lsf0bnc"><path class="s3fvc1qen"/><path class="k5darrm3j"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cryptocurrency:cnx" {...props}></Icon>
