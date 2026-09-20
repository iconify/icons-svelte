<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bcke9jbmh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="bcke9jbmh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:apache-kafka-light" {...props}></Icon>
