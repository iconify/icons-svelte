<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/upr5s1btc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1000,"height":1000};
const content = `<path class="upr5s1btc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="websymbol:progress-0" {...props}></Icon>
