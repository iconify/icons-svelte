<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wmg6x7buu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wmg6x7buu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:brand-walmart" {...props}></Icon>
