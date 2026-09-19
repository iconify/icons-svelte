<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tyyxxqb3x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="tyyxxqb3x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dashicons:editor-code-duplicate" {...props}></Icon>
