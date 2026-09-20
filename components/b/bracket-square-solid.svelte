<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mus218bnw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mus218bnw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixel:bracket-square-solid" {...props}></Icon>
