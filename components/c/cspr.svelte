<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kx2a4vdax.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kx2a4vdax"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:cspr" {...props}></Icon>
