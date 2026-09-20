<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/whh8hndrv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="whh8hndrv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:body-fill" {...props}></Icon>
