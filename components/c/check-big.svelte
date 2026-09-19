<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/ktzqkeb4w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ktzqkeb4w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ci:check-big" {...props}></Icon>
