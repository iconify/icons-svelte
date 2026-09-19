<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kc9qa6b_d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kc9qa6b_d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:roomsnursery" {...props}></Icon>
