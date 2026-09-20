<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/udb9-6b9f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="udb9-6b9f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:btc-line" {...props}></Icon>
