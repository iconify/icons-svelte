<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uac40eb1v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uac40eb1v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:link-forward" {...props}></Icon>
