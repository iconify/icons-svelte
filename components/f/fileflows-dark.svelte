<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/euuo8mlxo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="euuo8mlxo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:fileflows-dark" {...props}></Icon>
