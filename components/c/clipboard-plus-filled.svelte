<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gs91p4brs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gs91p4brs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:clipboard-plus-filled" {...props}></Icon>
