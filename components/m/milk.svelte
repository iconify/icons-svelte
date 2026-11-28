<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s1e1e9bhx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s1e1e9bhx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:milk" {...props}></Icon>
