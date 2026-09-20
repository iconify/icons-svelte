<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w2g0yejfb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="w2g0yejfb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:pocket-casts-logo-block" {...props}></Icon>
