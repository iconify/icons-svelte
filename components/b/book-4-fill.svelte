<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u_2xuvbiq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="u_2xuvbiq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:book-4-fill" {...props}></Icon>
