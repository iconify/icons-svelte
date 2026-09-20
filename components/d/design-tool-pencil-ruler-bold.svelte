<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mzjr1sbqy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mzjr1sbqy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:design-tool-pencil-ruler-bold" {...props}></Icon>
