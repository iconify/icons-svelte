<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/htc8-3ocq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="htc8-3ocq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:ankermake" {...props}></Icon>
