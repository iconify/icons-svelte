<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t7i7tqbhm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":50,"height":50};
const content = `<path class="t7i7tqbhm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="temaki:fishing-pier" {...props}></Icon>
