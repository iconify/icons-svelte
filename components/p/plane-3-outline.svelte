<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pe0m34kxw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="pe0m34kxw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:plane-3-outline" {...props}></Icon>
