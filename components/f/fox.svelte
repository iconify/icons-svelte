<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e_t-joczk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e_t-joczk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:fox" {...props}></Icon>
