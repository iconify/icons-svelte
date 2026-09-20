<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/k/k9_t36bgu.css';
import '../../css/o/ov9pr7bxz.css';
import '../../css/q/qn99s1bkd.css';
import '../../css/i/izrr8_ald.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="k9_t36bgu"/><path class="ov9pr7bxz"/><path class="qn99s1bkd"/><path class="izrr8_ald"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:radio-2" {...props}></Icon>
