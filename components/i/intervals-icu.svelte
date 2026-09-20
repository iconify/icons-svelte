<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f02lo6bya.css';
import '../../css/b/bdrh4zbik.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":462.9,"height":462.9};
const content = `<circle class="f02lo6bya"/><path class="bdrh4zbik"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:intervals-icu" {...props}></Icon>
