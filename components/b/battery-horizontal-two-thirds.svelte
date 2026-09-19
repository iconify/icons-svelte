<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ua926lwtx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ua926lwtx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:battery-horizontal-two-thirds" {...props}></Icon>
