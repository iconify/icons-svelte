<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cyu31v5md.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cyu31v5md"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="andrsrxn:arrow-end" {...props}></Icon>
