<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vky8wwlcb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="vky8wwlcb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:nomad-list-logo-block" {...props}></Icon>
