<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/maaxaibrw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="maaxaibrw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:delete-bin-3-fill" {...props}></Icon>
