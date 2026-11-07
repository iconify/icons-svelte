<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q2nrf10bf.css';
import '../../css/y/y_xe1sj7j.css';
import '../../css/m/m972g7bwn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q2nrf10bf"/><path class="y_xe1sj7j"/><path class="m972g7bwn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:folder-sync-bold-duotone" {...props}></Icon>
