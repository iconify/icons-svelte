<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eyktx9_mv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="eyktx9_mv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:bookmark-plus-alt-filled" {...props}></Icon>
