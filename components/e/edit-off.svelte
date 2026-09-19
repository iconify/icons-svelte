<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hb8-3blsk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="hb8-3blsk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:edit-off" {...props}></Icon>
