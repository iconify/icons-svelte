<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/je669obeu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="je669obeu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="majesticons:arrow-left" {...props}></Icon>
