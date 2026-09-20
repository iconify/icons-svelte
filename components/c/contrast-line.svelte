<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w833_db9u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w833_db9u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:contrast-line" {...props}></Icon>
