<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gijl0dblz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gijl0dblz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:inbox-sharp" {...props}></Icon>
