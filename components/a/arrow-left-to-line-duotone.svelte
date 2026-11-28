<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v0e0veb_i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="primary v0e0veb_i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:arrow-left-to-line-duotone" {...props}></Icon>
