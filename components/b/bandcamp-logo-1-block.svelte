<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/ti74s-boh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ti74s-boh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:bandcamp-logo-1-block" {...props}></Icon>
