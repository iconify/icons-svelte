<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rz-rw6wtu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rz-rw6wtu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:mobile-fingerprint" {...props}></Icon>
