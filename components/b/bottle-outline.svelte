<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/ks0odlsxw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ks0odlsxw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:bottle-outline" {...props}></Icon>
