<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m0si7bc9c.css';
import '../../css/r/r-xntnbat.css';
import '../../css/l/lq-q1ngth.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<rect class="m0si7bc9c"/><rect class="r-xntnbat"/><path class="lq-q1ngth"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:align-vertical-justify-center-filled" {...props}></Icon>
