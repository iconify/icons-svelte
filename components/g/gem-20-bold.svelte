<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/ldie7dbqp.css';
import '../../css/f/f25sq8ybr.css';
import '../../css/l/lztzvubai.css';
import '../../css/g/gnqh0y9sc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="ldie7dbqp"/><path class="f25sq8ybr"/><path class="lztzvubai"/><path class="gnqh0y9sc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:gem-20-bold" {...props}></Icon>
