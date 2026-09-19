<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qd0smrbkl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qd0smrbkl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:echo-gen-2" {...props}></Icon>
