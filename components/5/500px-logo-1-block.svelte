<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ato2_p4nh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ato2_p4nh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:500px-logo-1-block" {...props}></Icon>
