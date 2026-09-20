<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g1u5vzb7w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g1u5vzb7w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:cachet" {...props}></Icon>
