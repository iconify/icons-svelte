<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u3t-gxbfe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="u3t-gxbfe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixel:home-solid" {...props}></Icon>
