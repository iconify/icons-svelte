<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v4sou5zpq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="v4sou5zpq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cib:linkedin" {...props}></Icon>
