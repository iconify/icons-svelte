<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zcv99i1_c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zcv99i1_c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="majesticons:chats-line" {...props}></Icon>
