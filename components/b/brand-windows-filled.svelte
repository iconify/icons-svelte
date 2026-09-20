<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q2lv0vbah.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q2lv0vbah"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:brand-windows-filled" {...props}></Icon>
