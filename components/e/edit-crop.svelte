<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mu0s5dbco.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="mu0s5dbco"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zondicons:edit-crop" {...props}></Icon>
