<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k3zsr3b5w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k3zsr3b5w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="guidance:information-desk-symbol" {...props}></Icon>
