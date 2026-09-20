<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/inh5m1-1e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="inh5m1-1e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:fifa" {...props}></Icon>
