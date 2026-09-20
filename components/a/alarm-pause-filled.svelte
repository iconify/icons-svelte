<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vubu2cchl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="vubu2cchl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:alarm-pause-filled" {...props}></Icon>
