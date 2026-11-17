<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qz_yk6bme.css';
import '../../css/e/eig7_3bqg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="qz_yk6bme"/><path class="eig7_3bqg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:auditorr-dark" {...props}></Icon>
