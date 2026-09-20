<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k8pl06b_h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="k8pl06b_h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:refresh-1-fill" {...props}></Icon>
