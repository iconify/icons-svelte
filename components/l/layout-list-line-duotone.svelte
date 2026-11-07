<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/f/f8rmb_b-y.css';
import '../../css/t/tn-y1gb8r.css';
import '../../css/y/yxai8l1jn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="f8rmb_b-y"/><path class="tn-y1gb8r"/><path class="yxai8l1jn"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:layout-list-line-duotone" {...props}></Icon>
