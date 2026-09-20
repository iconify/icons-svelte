<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uhzcyvl8s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="uhzcyvl8s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:bebo-logo-block" {...props}></Icon>
