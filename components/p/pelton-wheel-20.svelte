<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/asx1s34lr.css';
import '../../css/l/l7gyyf0so.css';
import '../../css/x/xuvtw8qyt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="asx1s34lr"/><path class="l7gyyf0so"/><path class="xuvtw8qyt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:pelton-wheel-20" {...props}></Icon>
