<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k0m4y9b-a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k0m4y9b-a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:door-closed-locked" {...props}></Icon>
