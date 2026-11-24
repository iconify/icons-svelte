<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qw8a2j_zu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qw8a2j_zu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:brain-circuit-filled" {...props}></Icon>
