<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xb5yemjxa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="xb5yemjxa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:paperclip-small" {...props}></Icon>
