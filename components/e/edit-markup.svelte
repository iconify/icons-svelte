<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nkcsv_q9x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="nkcsv_q9x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gg:edit-markup" {...props}></Icon>
