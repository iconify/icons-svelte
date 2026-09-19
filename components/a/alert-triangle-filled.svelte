<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oxkhv8bmm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="oxkhv8bmm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:alert-triangle-filled" {...props}></Icon>
