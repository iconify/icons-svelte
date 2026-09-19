<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o6l5w6gsv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o6l5w6gsv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ci:circle-chevron-right" {...props}></Icon>
