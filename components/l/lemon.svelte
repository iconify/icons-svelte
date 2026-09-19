<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gn_saxb8w.css';
import '../../css/b/bkpxyzsbx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gn_saxb8w"/><path class="bkpxyzsbx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:lemon" {...props}></Icon>
