<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z3uo1db8t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z3uo1db8t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:dock-left-filled" {...props}></Icon>
