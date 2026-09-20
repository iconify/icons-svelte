<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uejcfd1cs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="uejcfd1cs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:end-point-diamond-solid" {...props}></Icon>
