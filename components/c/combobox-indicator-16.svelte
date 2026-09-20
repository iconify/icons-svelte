<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w2uonkolp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="w2uonkolp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:combobox-indicator-16" {...props}></Icon>
