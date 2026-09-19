<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zib0qbour.css';
import '../../css/k/k5pr-v-xw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zib0qbour"/><path class="k5pr-v-xw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:arrow-out-down-right-stroke-square" {...props}></Icon>
