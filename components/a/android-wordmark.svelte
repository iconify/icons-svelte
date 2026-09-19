<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bhmqpzncy.css';
import '../../css/x/xu8t15bjf.css';
import '../../css/z/zboiubcgk.css';
import '../../css/x/xnhmzobai.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="bhmqpzncy"/><path class="xu8t15bjf"/><path class="zboiubcgk"/><path class="xnhmzobai"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:android-wordmark" {...props}></Icon>
