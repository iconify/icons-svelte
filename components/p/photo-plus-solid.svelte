<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qhaasvw_e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="qhaasvw_e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="sidekickicons:photo-plus-solid" {...props}></Icon>
