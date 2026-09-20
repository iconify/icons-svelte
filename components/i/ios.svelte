<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kdx9_ybpf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kdx9_ybpf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:ios" {...props}></Icon>
