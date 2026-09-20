<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w1rn9v5yf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="w1rn9v5yf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:cloud-fill" {...props}></Icon>
