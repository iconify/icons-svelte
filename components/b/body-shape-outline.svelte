<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bnc4whb7q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="bnc4whb7q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:body-shape-outline" {...props}></Icon>
