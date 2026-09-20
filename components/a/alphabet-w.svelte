<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f8po9n06r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f8po9n06r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:alphabet-w" {...props}></Icon>
