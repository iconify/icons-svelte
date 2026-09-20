<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dcdz5x3sn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dcdz5x3sn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:ana" {...props}></Icon>
