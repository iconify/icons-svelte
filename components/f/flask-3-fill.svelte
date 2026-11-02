<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ej3jofb3f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ej3jofb3f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:flask-3-fill" {...props}></Icon>
