<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bcklpyb5z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bcklpyb5z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bitcoin-icons:info-outline" {...props}></Icon>
