<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/ru60jtz3b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ru60jtz3b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:passport-fill" {...props}></Icon>
