<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gj1rq-cte.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gj1rq-cte"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:accusoft" {...props}></Icon>
