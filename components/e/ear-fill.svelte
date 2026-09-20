<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xh-2k3bsn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xh-2k3bsn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:ear-fill" {...props}></Icon>
