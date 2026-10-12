<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/va-b4i6ve.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="va-b4i6ve"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:panel-bottom-dashed-filled" {...props}></Icon>
