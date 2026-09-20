<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/edj3zob3q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="edj3zob3q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:ampersand-bold" {...props}></Icon>
