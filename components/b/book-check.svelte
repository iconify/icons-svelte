<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/au1r8v_ro.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="au1r8v_ro"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:book-check" {...props}></Icon>
