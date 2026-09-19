<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h9oq7nbbm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h9oq7nbbm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:fluval-logo" {...props}></Icon>
