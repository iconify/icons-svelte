<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tggzodb7u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tggzodb7u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:layers-plus-filled" {...props}></Icon>
