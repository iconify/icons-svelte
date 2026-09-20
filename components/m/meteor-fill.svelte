<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/buxxueduh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="buxxueduh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:meteor-fill" {...props}></Icon>
