<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hxwq-ybae.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24,"left":-2,"top":-4.5};
const content = `<path class="hxwq-ybae"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="jam:newsletter-f" {...props}></Icon>
