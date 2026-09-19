<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fbvonubwu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fbvonubwu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="eva:person-fill" {...props}></Icon>
