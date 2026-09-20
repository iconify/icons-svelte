<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k0l5a0lfg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k0l5a0lfg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:coolify" {...props}></Icon>
