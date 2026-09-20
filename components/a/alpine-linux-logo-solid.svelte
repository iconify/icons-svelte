<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v29uo-_ja.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="v29uo-_ja"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:alpine-linux-logo-solid" {...props}></Icon>
