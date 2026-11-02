<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hafzs9bbt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hafzs9bbt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:color-picker-line" {...props}></Icon>
