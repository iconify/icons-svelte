<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zloyalpnw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zloyalpnw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:mist-line" {...props}></Icon>
