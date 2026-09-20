<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fj348nt0g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fj348nt0g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:near-field-communication-tap" {...props}></Icon>
