<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q9k9a11_b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q9k9a11_b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:dashboard-vert-line" {...props}></Icon>
