<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k3xbg8byz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="k3xbg8byz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:invoice-fill" {...props}></Icon>
