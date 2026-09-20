<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h94f_defi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h94f_defi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:gold" {...props}></Icon>
