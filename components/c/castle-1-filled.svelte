<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hlpvp0iiq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hlpvp0iiq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:castle-1-filled" {...props}></Icon>
