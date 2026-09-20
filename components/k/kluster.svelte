<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ol8hb0b1l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ol8hb0b1l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:kluster" {...props}></Icon>
