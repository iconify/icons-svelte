<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fj7__abnm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fj7__abnm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:blob-filled" {...props}></Icon>
