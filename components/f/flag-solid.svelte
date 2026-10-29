<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k5emwubkb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k5emwubkb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:flag-solid" {...props}></Icon>
