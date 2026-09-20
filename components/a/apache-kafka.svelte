<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g-jg9iuni.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="g-jg9iuni"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:apache-kafka" {...props}></Icon>
