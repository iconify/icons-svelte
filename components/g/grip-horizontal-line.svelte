<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wpwpxn17c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wpwpxn17c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uim:grip-horizontal-line" {...props}></Icon>
