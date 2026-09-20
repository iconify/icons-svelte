<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mj3qrn2fd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mj3qrn2fd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate-color:like" {...props}></Icon>
