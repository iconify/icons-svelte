<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cf4s-cb-u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cf4s-cb-u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:file-text-edit" {...props}></Icon>
