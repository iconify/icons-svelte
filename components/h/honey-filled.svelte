<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eynr-nwkr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="eynr-nwkr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:honey-filled" {...props}></Icon>
