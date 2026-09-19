<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/doeoiqb0y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="doeoiqb0y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:right-arrow" {...props}></Icon>
