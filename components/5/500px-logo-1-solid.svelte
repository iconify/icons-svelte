<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/whx76-5qm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="whx76-5qm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:500px-logo-1-solid" {...props}></Icon>
