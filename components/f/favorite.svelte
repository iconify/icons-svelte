<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nhyv_gnrk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nhyv_gnrk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uit:favorite" {...props}></Icon>
