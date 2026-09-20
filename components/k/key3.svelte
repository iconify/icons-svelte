<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o4ov4fb6d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="o4ov4fb6d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:key3" {...props}></Icon>
