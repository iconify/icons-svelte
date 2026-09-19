<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ifnrpjbzy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ifnrpjbzy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:folder-01" {...props}></Icon>
