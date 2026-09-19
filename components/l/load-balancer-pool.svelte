<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bzfby6bzz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="bzfby6bzz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:load-balancer-pool" {...props}></Icon>
