<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hei8_htdz.css';
import '../../css/q/q0ohsgrim.css';
import '../../css/s/snb525bvf.css';
import '../../css/z/zqel-5qvw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="hei8_htdz"/><path class="q0ohsgrim"/><path class="snb525bvf"/><path class="zqel-5qvw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:marker-wind-20-bold" {...props}></Icon>
