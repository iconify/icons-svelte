<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xzi11jbci.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="xzi11jbci"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:clipboard-filled" {...props}></Icon>
