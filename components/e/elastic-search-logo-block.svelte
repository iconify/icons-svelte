<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v7qkgz_uy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="v7qkgz_uy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:elastic-search-logo-block" {...props}></Icon>
