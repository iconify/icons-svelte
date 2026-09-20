<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e6i-u4buk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24,"left":-2,"top":-2};
const content = `<path class="e6i-u4buk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="jam:movie" {...props}></Icon>
