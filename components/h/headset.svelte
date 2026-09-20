<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bzu6jmbsd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="bzu6jmbsd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vaadin:headset" {...props}></Icon>
