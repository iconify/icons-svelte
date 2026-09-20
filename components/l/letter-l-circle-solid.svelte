<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/adh7oxwzu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="adh7oxwzu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:letter-l-circle-solid" {...props}></Icon>
