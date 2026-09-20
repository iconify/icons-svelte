<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ykfqj8cgr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ykfqj8cgr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:cloudways" {...props}></Icon>
