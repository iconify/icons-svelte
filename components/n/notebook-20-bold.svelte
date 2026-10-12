<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kmdpf7x1u.css';
import '../../css/i/i_ynx8bhx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="kmdpf7x1u"/><path class="i_ynx8bhx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:notebook-20-bold" {...props}></Icon>
