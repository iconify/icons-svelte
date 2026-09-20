<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/euf698iox.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="euf698iox"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:cloud-moon-hail" {...props}></Icon>
