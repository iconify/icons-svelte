<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qvbx-8bwp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qvbx-8bwp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fontisto:messenger" {...props}></Icon>
