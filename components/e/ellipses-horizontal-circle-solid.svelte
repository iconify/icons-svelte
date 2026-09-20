<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ug90z1_fl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ug90z1_fl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixel:ellipses-horizontal-circle-solid" {...props}></Icon>
