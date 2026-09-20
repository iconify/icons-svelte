<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tp4i0qbxq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tp4i0qbxq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:cirrus-ci" {...props}></Icon>
