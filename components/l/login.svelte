<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g-wpt7ytl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="g-wpt7ytl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="majesticons:login" {...props}></Icon>
