<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mo10oacue.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":17,"height":24};
const content = `<path class="mo10oacue"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fontisto:flash" {...props}></Icon>
