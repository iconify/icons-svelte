<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yu1bol9do.css';
import '../../css/c/crtuvabgp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="yu1bol9do"/><path class="crtuvabgp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:align-vertical-spacing-bold-duotone" {...props}></Icon>
