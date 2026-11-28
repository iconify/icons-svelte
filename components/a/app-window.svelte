<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m4kl6egzg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m4kl6egzg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:app-window" {...props}></Icon>
