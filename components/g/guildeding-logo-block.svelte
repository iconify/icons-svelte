<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ell9tsicb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ell9tsicb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:guildeding-logo-block" {...props}></Icon>
