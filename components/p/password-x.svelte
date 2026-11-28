<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lgzwr9b4f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lgzwr9b4f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:password-x" {...props}></Icon>
