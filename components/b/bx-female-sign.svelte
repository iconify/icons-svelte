<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gldgrx7rq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gldgrx7rq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bx-female-sign" {...props}></Icon>
