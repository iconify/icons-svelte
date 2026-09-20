<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j8u1jgjki.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="j8u1jgjki"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:arrow-up-right-from-circle" {...props}></Icon>
