<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l3a15mtdk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="l3a15mtdk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:firebase-logo-block" {...props}></Icon>
