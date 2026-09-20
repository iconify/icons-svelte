<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ajol6ub4x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ajol6ub4x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:clock-plus-outline" {...props}></Icon>
