<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kreqc1bua.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kreqc1bua"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:hand-sanitizer" {...props}></Icon>
