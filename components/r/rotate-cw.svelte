<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wkwaezb_n.css';
import '../../css/o/oj7j_1bgn.css';
import '../../css/s/ss3h7jkmy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wkwaezb_n wm-shadow"/><path class="oj7j_1bgn wm-k"/><path class="ss3h7jkmy wm-k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons-pastel:rotate-cw" {...props}></Icon>
