<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w8-yow--l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w8-yow--l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:grid-2x2-sharp" {...props}></Icon>
