<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vubt_7biv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vubt_7biv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:nfc" {...props}></Icon>
