<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n9k8p09iu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="n9k8p09iu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:md-bicycle" {...props}></Icon>
