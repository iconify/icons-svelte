<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jlld55b8l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="jlld55b8l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:home-1-solid" {...props}></Icon>
