<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c52fk4sax.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c52fk4sax"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:layout-leftbar-open-line" {...props}></Icon>
