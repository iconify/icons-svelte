<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gu75auegt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gu75auegt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:ad-filled" {...props}></Icon>
