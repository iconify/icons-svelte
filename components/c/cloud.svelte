<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hqwvg3bhw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hqwvg3bhw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="humbleicons:cloud" {...props}></Icon>
