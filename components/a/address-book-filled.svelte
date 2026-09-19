<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y012yebaw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="y012yebaw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:address-book-filled" {...props}></Icon>
