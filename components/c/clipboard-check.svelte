<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lul-u6mqz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lul-u6mqz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mi:clipboard-check" {...props}></Icon>
