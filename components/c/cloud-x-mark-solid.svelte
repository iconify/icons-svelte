<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t98k1grdv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="t98k1grdv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="sidekickicons:cloud-x-mark-solid" {...props}></Icon>
