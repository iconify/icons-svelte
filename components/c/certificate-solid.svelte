<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mco3pablm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mco3pablm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:certificate-solid" {...props}></Icon>
