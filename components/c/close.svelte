<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oky91eb4w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="oky91eb4w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gg:close" {...props}></Icon>
