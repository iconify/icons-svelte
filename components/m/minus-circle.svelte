<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/km-tr-1rj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24,"left":-2,"top":-2};
const content = `<path class="km-tr-1rj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="jam:minus-circle" {...props}></Icon>
