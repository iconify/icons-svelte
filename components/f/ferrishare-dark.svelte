<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i1iycg2ku.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="i1iycg2ku"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:ferrishare-dark" {...props}></Icon>
