<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k5pr-v-xw.css';
import '../../css/y/yf1avm6ta.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k5pr-v-xw"/><path class="yf1avm6ta"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:arrow-out-down-right-square" {...props}></Icon>
