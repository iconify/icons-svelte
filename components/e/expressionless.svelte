<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h32t530tv.css';
import '../../css/n/n9cednr3v.css';
import '../../css/y/y3g7q6brp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="h32t530tv"/><path class="n9cednr3v"/><path class="y3g7q6brp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fxemoji:expressionless" {...props}></Icon>
