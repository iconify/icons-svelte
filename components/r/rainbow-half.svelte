<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z6ilqbb1w.css';
import '../../css/q/qlpwkbctq.css';
import '../../css/c/ca79ulb_a.css';
import '../../css/t/tq_gmsbqd.css';
import '../../css/z/z6q2bfbwt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z6ilqbb1w"/><path class="qlpwkbctq"/><path class="ca79ulb_a"/><path class="tq_gmsbqd"/><path class="z6q2bfbwt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:rainbow-half" {...props}></Icon>
