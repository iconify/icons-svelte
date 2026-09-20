<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/ro6ec6buy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ro6ec6buy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:eye-filled" {...props}></Icon>
