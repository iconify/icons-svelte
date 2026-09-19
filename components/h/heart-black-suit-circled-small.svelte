<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wygg5fb5y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="wygg5fb5y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:heart-black-suit-circled-small" {...props}></Icon>
