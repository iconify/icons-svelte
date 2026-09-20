<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q3gl-5byj.css';
import '../../css/a/aepino0ac.css';
import '../../css/g/go-_ugbik.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="q3gl-5byj"/><path class="aepino0ac"/><path class="go-_ugbik"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:bruno" {...props}></Icon>
