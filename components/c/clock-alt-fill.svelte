<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oc-lvac0j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="oc-lvac0j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:clock-alt-fill" {...props}></Icon>
