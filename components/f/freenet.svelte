<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gi_v-c7ta.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gi_v-c7ta"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:freenet" {...props}></Icon>
