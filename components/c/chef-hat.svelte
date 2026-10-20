<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sbp_cdbbx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sbp_cdbbx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:chef-hat" {...props}></Icon>
