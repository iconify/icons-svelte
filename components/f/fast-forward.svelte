<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h4wm4121x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h4wm4121x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi-light:fast-forward" {...props}></Icon>
