<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qc8alin5r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="qc8alin5r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:octagon-pause-filled" {...props}></Icon>
