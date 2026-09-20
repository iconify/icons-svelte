<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l96-r8sfd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="l96-r8sfd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:card-2-outline" {...props}></Icon>
