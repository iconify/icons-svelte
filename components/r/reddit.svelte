<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/czvai8b2k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="czvai8b2k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ci:reddit" {...props}></Icon>
