<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/km263xb3y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="km263xb3y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:file-heart" {...props}></Icon>
