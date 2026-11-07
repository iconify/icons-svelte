<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i201z6bwc.css';
import '../../css/n/nhyj9zb8o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i201z6bwc"/><path clip-rule="evenodd" class="nhyj9zb8o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:cup-first-outline" {...props}></Icon>
