<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/ld-6nbc_y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ld-6nbc_y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:arrow-down-right" {...props}></Icon>
