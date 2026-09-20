<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c6r3seouz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c6r3seouz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:layout-top-2-fill" {...props}></Icon>
