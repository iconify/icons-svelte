<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jeqa6dbzi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jeqa6dbzi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:bit" {...props}></Icon>
