<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cjp8bhb5z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cjp8bhb5z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi-light:format-list-numbers" {...props}></Icon>
