<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uob0f-byp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uob0f-byp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="eva:edit-outline" {...props}></Icon>
