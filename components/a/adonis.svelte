<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gnxf60wjv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gnxf60wjv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:adonis" {...props}></Icon>
