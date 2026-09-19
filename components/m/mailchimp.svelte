<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t8u7_hugl.css';
import '../../css/e/e9di-eb1o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t8u7_hugl"/><path class="e9di-eb1o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxl:mailchimp" {...props}></Icon>
