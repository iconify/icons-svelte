<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eu_8vhbfj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="eu_8vhbfj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:more-2-fill" {...props}></Icon>
