<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p40sy6z0u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="p40sy6z0u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:circle-transfer-diag" {...props}></Icon>
