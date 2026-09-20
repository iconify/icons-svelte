<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iflla3gmr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="iflla3gmr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:face-frown-fill" {...props}></Icon>
