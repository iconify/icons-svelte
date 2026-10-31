<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sq857obgn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="sq857obgn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="sidekickicons:headphones-slash-16-solid" {...props}></Icon>
