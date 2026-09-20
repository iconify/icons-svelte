<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/efk22ccyi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="efk22ccyi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:card-edit-filled" {...props}></Icon>
