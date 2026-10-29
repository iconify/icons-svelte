<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gu6wyi_ja.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gu6wyi_ja"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:passport-solid" {...props}></Icon>
