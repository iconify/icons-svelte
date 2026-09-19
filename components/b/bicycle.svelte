<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tbq9c8hyy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":34,"height":24};
const content = `<path class="tbq9c8hyy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fontisto:bicycle" {...props}></Icon>
