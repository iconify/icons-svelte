<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b_p7mla1l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b_p7mla1l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:caret-up-square-filled" {...props}></Icon>
