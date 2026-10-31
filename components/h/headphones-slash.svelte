<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uar1gl6yh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uar1gl6yh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="sidekickicons:headphones-slash" {...props}></Icon>
