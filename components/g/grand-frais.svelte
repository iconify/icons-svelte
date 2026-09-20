<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lfg7h4bnt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lfg7h4bnt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:grand-frais" {...props}></Icon>
