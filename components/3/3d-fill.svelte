<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kpv4762am.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="kpv4762am"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:3d-fill" {...props}></Icon>
