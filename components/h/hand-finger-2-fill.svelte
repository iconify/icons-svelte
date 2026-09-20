<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jijy0rbpw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="jijy0rbpw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:hand-finger-2-fill" {...props}></Icon>
