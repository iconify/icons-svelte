<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f82_ylk6e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f82_ylk6e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:align-left-solid" {...props}></Icon>
