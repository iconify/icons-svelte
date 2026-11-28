<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i2qwz7y9j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i2qwz7y9j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:pumpkin-heart" {...props}></Icon>
