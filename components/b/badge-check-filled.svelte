<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hzrmuq56m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="hzrmuq56m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:badge-check-filled" {...props}></Icon>
