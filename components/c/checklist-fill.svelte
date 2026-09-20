<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d_u2orb0n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d_u2orb0n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:checklist-fill" {...props}></Icon>
