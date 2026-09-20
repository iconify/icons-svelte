<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hjns-peoc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="hjns-peoc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:firebase-logo-solid" {...props}></Icon>
