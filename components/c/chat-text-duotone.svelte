<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/w/wlt1rbb1o.css';
import '../../css/e/eaukp4b_y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="wlt1rbb1o"/><path class="eaukp4b_y"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:chat-text-duotone" {...props}></Icon>
