<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qo4j70bbm.css';
import '../../css/v/v21ewjqfm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="qo4j70bbm"/><path class="v21ewjqfm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:biofuel-20-bold" {...props}></Icon>
