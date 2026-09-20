<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/um76j9znb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="um76j9znb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:adobe-xd-logo-block" {...props}></Icon>
