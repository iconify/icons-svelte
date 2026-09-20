<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d-7og1lim.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d-7og1lim"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:json-alt-4-line" {...props}></Icon>
