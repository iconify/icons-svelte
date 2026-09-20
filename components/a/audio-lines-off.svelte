<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mjslyj_rv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mjslyj_rv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:audio-lines-off" {...props}></Icon>
