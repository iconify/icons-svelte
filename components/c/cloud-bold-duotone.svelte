<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gk87vthwz.css';
import '../../css/v/v7o6jqpbt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="gk87vthwz"/><path class="v7o6jqpbt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:cloud-bold-duotone" {...props}></Icon>
