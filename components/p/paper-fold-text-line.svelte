<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m5s7h4b-c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m5s7h4b-c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="majesticons:paper-fold-text-line" {...props}></Icon>
