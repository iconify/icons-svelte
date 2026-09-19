<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r_n7dobql.css';
import '../../css/n/nzlfk-b_q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r_n7dobql"/><path class="nzlfk-b_q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:rotate-cw-10" {...props}></Icon>
