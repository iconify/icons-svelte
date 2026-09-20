<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cv4d2ta5x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24,"left":-2,"top":-6};
const content = `<path class="cv4d2ta5x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="jam:coffee-cup" {...props}></Icon>
