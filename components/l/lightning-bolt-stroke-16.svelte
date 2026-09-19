<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qydy7ebjm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="qydy7ebjm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:lightning-bolt-stroke-16" {...props}></Icon>
