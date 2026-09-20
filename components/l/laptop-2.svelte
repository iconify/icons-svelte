<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o_ffcxrtp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o_ffcxrtp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-cyber:laptop-2" {...props}></Icon>
