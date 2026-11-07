<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z_zrozxsx.css';
import '../../css/k/k5fmwhakm.css';
import '../../css/p/pq3xuilmm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z_zrozxsx"/><path clip-rule="evenodd" class="k5fmwhakm"/><path clip-rule="evenodd" class="pq3xuilmm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:card-transfer-bold" {...props}></Icon>
