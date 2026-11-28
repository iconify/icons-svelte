<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/at31kobgd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="at31kobgd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:paint-bucket-check" {...props}></Icon>
