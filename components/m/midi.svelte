<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/ju1gmkind.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ju1gmkind"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:midi" {...props}></Icon>
