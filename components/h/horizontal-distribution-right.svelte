<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kc9trpg0o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kc9trpg0o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:horizontal-distribution-right" {...props}></Icon>
