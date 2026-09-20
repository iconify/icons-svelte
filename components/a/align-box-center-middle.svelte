<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u93049byl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="u93049byl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:align-box-center-middle" {...props}></Icon>
