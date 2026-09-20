<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fcc6lny6x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fcc6lny6x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:gnu-emacs" {...props}></Icon>
