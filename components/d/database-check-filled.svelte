<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/grda5wb_p.css';
import '../../css/e/e_r9uibzg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="grda5wb_p"/><path class="e_r9uibzg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:database-check-filled" {...props}></Icon>
