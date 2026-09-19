<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hen0ml0nu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hen0ml0nu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:delivery" {...props}></Icon>
