<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hk40vyc-m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hk40vyc-m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:cursor-arrow-rays" {...props}></Icon>
