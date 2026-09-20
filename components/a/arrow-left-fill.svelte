<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d9ysj83kw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d9ysj83kw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:arrow-left-fill" {...props}></Icon>
