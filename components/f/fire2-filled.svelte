<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j_ac9abqm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="j_ac9abqm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:fire2-filled" {...props}></Icon>
