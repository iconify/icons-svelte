<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q0dhg0k_s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q0dhg0k_s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:arrow-back" {...props}></Icon>
