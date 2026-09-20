<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/unav5rb9k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="unav5rb9k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:kubetail-dark" {...props}></Icon>
