<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m-2yo-qdb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":25,"height":24};
const content = `<path class="m-2yo-qdb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fontisto:linkedin" {...props}></Icon>
