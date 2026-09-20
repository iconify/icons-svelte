<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hei1iof_y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hei1iof_y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:inception-labs" {...props}></Icon>
