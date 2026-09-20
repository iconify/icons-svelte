<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ur72ib6mp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ur72ib6mp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:filezilla-dark" {...props}></Icon>
