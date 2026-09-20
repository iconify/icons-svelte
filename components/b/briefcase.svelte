<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ip8n-4bdw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ip8n-4bdw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi-light:briefcase" {...props}></Icon>
