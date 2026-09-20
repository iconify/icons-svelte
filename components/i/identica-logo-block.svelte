<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l5eceub-s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="l5eceub-s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:identica-logo-block" {...props}></Icon>
