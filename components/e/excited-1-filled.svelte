<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ooifsjb9q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ooifsjb9q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:excited-1-filled" {...props}></Icon>
