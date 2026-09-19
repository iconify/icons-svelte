<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gsuqm5b8o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gsuqm5b8o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bx-file-blank" {...props}></Icon>
