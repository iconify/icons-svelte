<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dxxo6lb9u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="dxxo6lb9u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:magnifying-glass-remix" {...props}></Icon>
