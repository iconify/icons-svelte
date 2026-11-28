<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qxgpe524t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qxgpe524t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:cooking-pot-plus" {...props}></Icon>
