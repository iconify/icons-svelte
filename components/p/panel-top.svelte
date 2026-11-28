<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g0vzrlr6u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g0vzrlr6u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:panel-top" {...props}></Icon>
