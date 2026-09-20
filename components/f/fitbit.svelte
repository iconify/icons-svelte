<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t9aoe4pgc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t9aoe4pgc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:fitbit" {...props}></Icon>
