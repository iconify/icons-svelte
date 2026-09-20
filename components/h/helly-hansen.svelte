<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gpj-9pbfz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gpj-9pbfz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:helly-hansen" {...props}></Icon>
