<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z8gg_bcnh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="z8gg_bcnh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:battery-vertical-half" {...props}></Icon>
