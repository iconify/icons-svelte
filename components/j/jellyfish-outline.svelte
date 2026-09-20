<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cnzim0yoo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cnzim0yoo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:jellyfish-outline" {...props}></Icon>
