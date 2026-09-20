<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gg1e5gzxk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="gg1e5gzxk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:amd-logo-solid" {...props}></Icon>
