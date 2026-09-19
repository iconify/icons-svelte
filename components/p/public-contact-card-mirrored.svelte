<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jix789b5n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="jix789b5n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:public-contact-card-mirrored" {...props}></Icon>
