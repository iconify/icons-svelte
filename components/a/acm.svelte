<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ea9wp1b6i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="ea9wp1b6i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cib:acm" {...props}></Icon>
