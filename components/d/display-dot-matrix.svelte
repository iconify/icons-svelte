<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q_s_vqb5k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="q_s_vqb5k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:display-dot-matrix" {...props}></Icon>
