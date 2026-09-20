<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mh4rsybdo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mh4rsybdo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:chef-hat-filled" {...props}></Icon>
