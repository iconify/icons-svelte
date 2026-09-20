<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d7op48boq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d7op48boq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:artifacthub" {...props}></Icon>
