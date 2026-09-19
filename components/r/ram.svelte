<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gz2gvrbvm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gz2gvrbvm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:ram" {...props}></Icon>
