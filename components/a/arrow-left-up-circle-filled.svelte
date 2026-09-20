<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gr83jrbsk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gr83jrbsk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:arrow-left-up-circle-filled" {...props}></Icon>
