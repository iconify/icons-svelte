<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zasjcbc-u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zasjcbc-u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="eva:arrow-down-fill" {...props}></Icon>
