<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zit9a7yxo.css';
import '../../css/b/br0wqld1w.css';
import '../../css/h/hqpwl64dn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zit9a7yxo"/><path class="br0wqld1w"/><path clip-rule="evenodd" class="hqpwl64dn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:fridge-outline" {...props}></Icon>
