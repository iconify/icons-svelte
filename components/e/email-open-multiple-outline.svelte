<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nu_2z9bjc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nu_2z9bjc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:email-open-multiple-outline" {...props}></Icon>
