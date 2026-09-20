<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hb178zbrx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hb178zbrx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:json" {...props}></Icon>
