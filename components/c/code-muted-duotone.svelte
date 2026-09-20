<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dq_v0_2ro.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dq_v0_2ro"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:code-muted-duotone" {...props}></Icon>
