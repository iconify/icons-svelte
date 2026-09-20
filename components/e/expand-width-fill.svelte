<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hn5s1xbha.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hn5s1xbha"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:expand-width-fill" {...props}></Icon>
