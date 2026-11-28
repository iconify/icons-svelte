<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sd4jgsgnu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sd4jgsgnu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:flow-sort-solid" {...props}></Icon>
