<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b381prbzq.css';
import '../../css/s/slbg-zbbp.css';
import '../../css/o/oputujbyf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="b381prbzq"/><path class="slbg-zbbp"/><path class="oputujbyf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:letter-spacing-48" {...props}></Icon>
