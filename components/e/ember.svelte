<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v7qw6pbnm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="v7qw6pbnm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:ember" {...props}></Icon>
