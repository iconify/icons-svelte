<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fj3g-36wb.css';
import '../../css/h/hoczzqb5s.css';
import '../../css/m/ml860nrta.css';
import '../../css/e/eqh2q3bcc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="fj3g-36wb"/><path class="hoczzqb5s"/><path class="ml860nrta"/><path class="eqh2q3bcc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:multimeter-20" {...props}></Icon>
