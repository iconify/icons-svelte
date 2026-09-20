<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e9rxa3bsd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e9rxa3bsd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:book-open-page-variant" {...props}></Icon>
