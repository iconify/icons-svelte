<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pei8s1mvn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="pei8s1mvn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:flow-merge" {...props}></Icon>
