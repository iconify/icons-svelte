<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/urv425-uw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="urv425-uw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:candy-solid" {...props}></Icon>
