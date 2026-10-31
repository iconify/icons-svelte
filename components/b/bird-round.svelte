<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k0slv-0of.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k0slv-0of"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:bird-round" {...props}></Icon>
