<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/br11ttb2b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="br11ttb2b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uim:pentagon" {...props}></Icon>
