<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f0y859buk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="f0y859buk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:clipboard-small-filled" {...props}></Icon>
