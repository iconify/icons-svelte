<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tm4fpf_uw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tm4fpf_uw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:lazyvim" {...props}></Icon>
