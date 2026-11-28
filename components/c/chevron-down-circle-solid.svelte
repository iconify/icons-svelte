<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gkn55lbxr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gkn55lbxr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:chevron-down-circle-solid" {...props}></Icon>
