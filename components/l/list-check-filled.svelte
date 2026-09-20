<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jriorrg2f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="jriorrg2f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:list-check-filled" {...props}></Icon>
