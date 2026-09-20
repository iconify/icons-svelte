<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i3wwp1e6l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="i3wwp1e6l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="picon:muffin" {...props}></Icon>
