<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gi16_abqf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="gi16_abqf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gravity-ui:chart-pie" {...props}></Icon>
