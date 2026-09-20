<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kkdqsnrvq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kkdqsnrvq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:osf" {...props}></Icon>
