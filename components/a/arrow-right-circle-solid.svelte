<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kiayg_b0h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="kiayg_b0h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:arrow-right-circle-solid" {...props}></Icon>
