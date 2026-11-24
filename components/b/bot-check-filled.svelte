<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e_r9uibzg.css';
import '../../css/c/cdu9hfbeq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e_r9uibzg"/><path clip-rule="evenodd" class="cdu9hfbeq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:bot-check-filled" {...props}></Icon>
