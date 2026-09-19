<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nwe13cc8d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="nwe13cc8d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:anchor-small" {...props}></Icon>
