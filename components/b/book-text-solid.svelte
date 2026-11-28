<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jk--uubxc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jk--uubxc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:book-text-solid" {...props}></Icon>
