<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tx20v6byn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tx20v6byn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:home-alt-01-filled" {...props}></Icon>
