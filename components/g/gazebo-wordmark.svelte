<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i9n_e1oth.css';
import '../../css/l/l6e1lqxzx.css';
import '../../css/f/fmobx0btv.css';
import '../../css/u/u1jdc_bkh.css';
import '../../css/k/k8b4iz71r.css';
import '../../css/j/j42-rebgt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="i9n_e1oth"/><path class="l6e1lqxzx"/><path class="fmobx0btv"/><path class="u1jdc_bkh"/><path class="k8b4iz71r"/><path class="j42-rebgt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:gazebo-wordmark" {...props}></Icon>
