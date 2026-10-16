<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mg0d9fh6u.css';
import '../../css/c/c_b1bdc7i.css';
import '../../css/e/e5bjqi7bk.css';
import '../../css/q/qhh6ftvhk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="mg0d9fh6u"/><path class="c_b1bdc7i"/><path class="e5bjqi7bk"/><path class="qhh6ftvhk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:camera-switch-20-bold" {...props}></Icon>
