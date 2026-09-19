<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rusai8b6b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rusai8b6b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:caret-down-square-filled" {...props}></Icon>
