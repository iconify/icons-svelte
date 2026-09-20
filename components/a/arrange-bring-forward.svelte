<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xz2wkllcr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xz2wkllcr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi-light:arrange-bring-forward" {...props}></Icon>
