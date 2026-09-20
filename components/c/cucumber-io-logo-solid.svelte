<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lca7sdy8u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="lca7sdy8u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:cucumber-io-logo-solid" {...props}></Icon>
