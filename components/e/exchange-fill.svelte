<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y9m30gb0r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="y9m30gb0r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:exchange-fill" {...props}></Icon>
