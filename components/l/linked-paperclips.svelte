<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/t/ti92cbmei.css';
import '../../css/y/y_g29ma4v.css';
import '../../css/e/e_ttht3ap.css';
import '../../css/m/m56q2cczf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path class="ti92cbmei"/><path class="y_g29ma4v"/><path class="e_ttht3ap"/><path class="m56q2cczf"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-emoji-flat:linked-paperclips" {...props}></Icon>
