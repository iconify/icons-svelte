<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y6-g0sprb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="y6-g0sprb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:cable-car-filled" {...props}></Icon>
