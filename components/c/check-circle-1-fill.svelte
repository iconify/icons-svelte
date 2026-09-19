<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k7g7l5bvq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="k7g7l5bvq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:check-circle-1-fill" {...props}></Icon>
