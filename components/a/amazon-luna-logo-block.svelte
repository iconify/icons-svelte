<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hvo319btz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="hvo319btz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:amazon-luna-logo-block" {...props}></Icon>
