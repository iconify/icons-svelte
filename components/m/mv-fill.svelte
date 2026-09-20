<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eso9agb5s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="eso9agb5s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:mv-fill" {...props}></Icon>
