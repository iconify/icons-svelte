<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/em5st3bao.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="em5st3bao"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:apache-kafka-dark" {...props}></Icon>
