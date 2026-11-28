<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/af3qo4aum.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="af3qo4aum"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:file-zip" {...props}></Icon>
