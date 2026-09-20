<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gzx73-76o.css';
import '../../css/f/f6hx_4p6c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gzx73-76o"/><path class="f6hx_4p6c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:avinoc" {...props}></Icon>
