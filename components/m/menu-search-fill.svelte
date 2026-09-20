<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v-pjvdfqj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="v-pjvdfqj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:menu-search-fill" {...props}></Icon>
