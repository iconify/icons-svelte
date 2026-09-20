<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gv8g7sb_b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="gv8g7sb_b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:atomic" {...props}></Icon>
