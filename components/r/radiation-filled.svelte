<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l3eh531-p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="l3eh531-p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:radiation-filled" {...props}></Icon>
