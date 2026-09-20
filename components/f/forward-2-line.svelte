<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/ms5l_luvw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ms5l_luvw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:forward-2-line" {...props}></Icon>
