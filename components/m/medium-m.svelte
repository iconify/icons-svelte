<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zlz8g7oln.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zlz8g7oln"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:medium-m" {...props}></Icon>
