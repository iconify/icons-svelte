<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mjh9fteip.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="mjh9fteip"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:hi-five-logo-solid" {...props}></Icon>
