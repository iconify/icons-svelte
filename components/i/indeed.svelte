<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hek-sbbhn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="hek-sbbhn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cib:indeed" {...props}></Icon>
