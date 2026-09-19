<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/ss_nhe6tp.css';
import '../../css/t/trav0txtl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ss_nhe6tp"/><path class="trav0txtl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cuida:at-outline" {...props}></Icon>
