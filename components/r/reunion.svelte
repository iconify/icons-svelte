<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tj1g41blw.css';
import '../../css/l/lw6oj00xq.css';
import '../../css/s/sqitbfasi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":30,"height":24};
const content = `<path class="tj1g41blw"/><path class="lw6oj00xq"/><path class="sqitbfasi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler-flags:reunion" {...props}></Icon>
