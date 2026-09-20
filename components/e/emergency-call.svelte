<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k3osa8bkl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k3osa8bkl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:emergency-call" {...props}></Icon>
