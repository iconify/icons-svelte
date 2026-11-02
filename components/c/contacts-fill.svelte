<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i1gr_acfz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i1gr_acfz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:contacts-fill" {...props}></Icon>
