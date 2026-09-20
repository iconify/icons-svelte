<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/ces36_uah.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ces36_uah"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:forward-15s" {...props}></Icon>
