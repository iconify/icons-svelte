<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u7wvp7oxw.css';
import '../../css/s/s4dgi_7mp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="u7wvp7oxw"/><path class="s4dgi_7mp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:calendar-x-2-filled" {...props}></Icon>
