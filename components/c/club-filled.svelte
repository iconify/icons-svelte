<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ygh1u7suj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ygh1u7suj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:club-filled" {...props}></Icon>
