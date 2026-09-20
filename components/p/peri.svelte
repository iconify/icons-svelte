<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nz1vnob6y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nz1vnob6y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:peri" {...props}></Icon>
