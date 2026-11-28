<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w0nl-j1kl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w0nl-j1kl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:arrow-up-long-solid" {...props}></Icon>
