<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dioopbc0k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dioopbc0k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:mail-open-check" {...props}></Icon>
