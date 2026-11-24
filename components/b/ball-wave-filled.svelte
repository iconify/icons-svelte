<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v72yvk6dr.css';
import '../../css/e/e2m9rbc6m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="v72yvk6dr"/><path clip-rule="evenodd" class="e2m9rbc6m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:ball-wave-filled" {...props}></Icon>
