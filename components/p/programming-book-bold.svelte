<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q2d_vachs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q2d_vachs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:programming-book-bold" {...props}></Icon>
