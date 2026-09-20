<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qq6snzbla.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qq6snzbla"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:appsmith" {...props}></Icon>
