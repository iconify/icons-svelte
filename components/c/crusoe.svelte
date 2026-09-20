<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t4621jb0b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t4621jb0b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:crusoe" {...props}></Icon>
