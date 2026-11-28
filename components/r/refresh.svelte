<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h3zhikb9i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h3zhikb9i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:refresh" {...props}></Icon>
