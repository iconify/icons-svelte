<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n9w-19l9h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="n9w-19l9h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="eva:film-fill" {...props}></Icon>
