<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q04i1-nof.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q04i1-nof"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:rescuetime" {...props}></Icon>
