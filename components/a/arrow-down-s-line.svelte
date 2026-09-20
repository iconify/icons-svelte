<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k3aek7nzy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k3aek7nzy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:arrow-down-s-line" {...props}></Icon>
