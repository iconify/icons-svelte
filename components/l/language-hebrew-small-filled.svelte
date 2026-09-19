<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jo0vp2bog.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="jo0vp2bog"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:language-hebrew-small-filled" {...props}></Icon>
