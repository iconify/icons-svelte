<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p7v4o8g4h.css';
import '../../css/o/o8973hbfi.css';
import '../../css/c/cd-k0ccfw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="p7v4o8g4h"/><path class="o8973hbfi"/><path class="cd-k0ccfw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixel:gaming" {...props}></Icon>
