<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p4i8jt03t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="p4i8jt03t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:icq" {...props}></Icon>
