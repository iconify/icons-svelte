<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rngyk4bhn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rngyk4bhn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ci:house-add" {...props}></Icon>
