<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ekdku3bzp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24,"left":-6,"top":-2};
const content = `<path class="ekdku3bzp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="jam:pocket-watch-f" {...props}></Icon>
