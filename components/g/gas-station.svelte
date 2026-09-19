<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ysus3cbyg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ysus3cbyg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:gas-station" {...props}></Icon>
