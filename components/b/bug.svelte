<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t73q5-q3m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t73q5-q3m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="proicons:bug" {...props}></Icon>
