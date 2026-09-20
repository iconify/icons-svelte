<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rtkpbrjou.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rtkpbrjou"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:9gag" {...props}></Icon>
