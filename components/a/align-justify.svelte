<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yjfhaw4wq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yjfhaw4wq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:align-justify" {...props}></Icon>
