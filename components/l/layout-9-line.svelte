<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u9x30lekw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="u9x30lekw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:layout-9-line" {...props}></Icon>
