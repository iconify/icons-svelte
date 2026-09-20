<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/ktn4qlgbd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ktn4qlgbd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:book-read-line" {...props}></Icon>
