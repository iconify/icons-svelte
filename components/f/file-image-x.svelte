<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v9m6x3g9b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="v9m6x3g9b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:file-image-x" {...props}></Icon>
