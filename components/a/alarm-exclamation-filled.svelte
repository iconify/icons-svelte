<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pg4551bmt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pg4551bmt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:alarm-exclamation-filled" {...props}></Icon>
