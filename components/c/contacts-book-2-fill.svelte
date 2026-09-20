<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/ccq__ub1i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ccq__ub1i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:contacts-book-2-fill" {...props}></Icon>
