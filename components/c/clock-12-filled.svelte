<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/ttpet3brj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ttpet3brj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:clock-12-filled" {...props}></Icon>
