<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tss2zerei.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="tss2zerei"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:loom-logo-solid" {...props}></Icon>
