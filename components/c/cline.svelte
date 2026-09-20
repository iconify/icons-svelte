<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/th2o4bz-a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="th2o4bz-a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:cline" {...props}></Icon>
