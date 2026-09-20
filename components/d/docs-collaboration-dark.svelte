<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uhyzs1izz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="uhyzs1izz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:docs-collaboration-dark" {...props}></Icon>
