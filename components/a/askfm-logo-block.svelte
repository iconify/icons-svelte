<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/od05kr4ry.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="od05kr4ry"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:askfm-logo-block" {...props}></Icon>
