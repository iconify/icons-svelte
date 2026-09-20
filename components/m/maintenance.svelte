<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rnsqrmb-o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rnsqrmb-o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-cyber:maintenance" {...props}></Icon>
