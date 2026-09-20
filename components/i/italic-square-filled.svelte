<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ip591cb9f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ip591cb9f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:italic-square-filled" {...props}></Icon>
