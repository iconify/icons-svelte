<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fss36bbna.css';
import '../../css/w/w3qyplb8m.css';
import '../../css/g/g1oxkbkoa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="fss36bbna"/><path class="w3qyplb8m"/><path class="g1oxkbkoa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:domainmod-light" {...props}></Icon>
