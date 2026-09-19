<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kqtl7_d8i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kqtl7_d8i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:grid-row-bottom" {...props}></Icon>
