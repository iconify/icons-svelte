<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w5i7ibc6a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="w5i7ibc6a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:heart-slash-circle-fill" {...props}></Icon>
