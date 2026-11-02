<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jurw6yb4s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jurw6yb4s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:chef-hat-fill" {...props}></Icon>
