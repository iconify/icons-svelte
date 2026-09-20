<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/ttiz4u36y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ttiz4u36y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:card-transfer-outline" {...props}></Icon>
