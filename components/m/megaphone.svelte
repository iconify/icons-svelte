<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c-7j2m-uc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c-7j2m-uc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:megaphone" {...props}></Icon>
