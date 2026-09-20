<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dxxo2obwx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dxxo2obwx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-cyber:bank-1" {...props}></Icon>
