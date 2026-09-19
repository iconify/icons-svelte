<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oovqvoxkv.css';
import '../../css/k/k_u3wubkw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="oovqvoxkv"/><path class="k_u3wubkw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="eva:compass-fill" {...props}></Icon>
