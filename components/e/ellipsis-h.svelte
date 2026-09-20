<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/btwot6bhb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="btwot6bhb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uis:ellipsis-h" {...props}></Icon>
