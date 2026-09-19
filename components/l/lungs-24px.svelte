<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cm1j0bb9a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cm1j0bb9a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:lungs-24px" {...props}></Icon>
