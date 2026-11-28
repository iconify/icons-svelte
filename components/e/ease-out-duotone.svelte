<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hugsjk8ob.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hugsjk8ob primary"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:ease-out-duotone" {...props}></Icon>
