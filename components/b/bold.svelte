<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uq9przbhr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24,"left":-8.5,"top":-7};
const content = `<path class="uq9przbhr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="jam:bold" {...props}></Icon>
