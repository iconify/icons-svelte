<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iglyc9bzd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="iglyc9bzd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:hanger" {...props}></Icon>
