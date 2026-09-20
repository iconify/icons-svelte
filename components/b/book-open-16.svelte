<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tcsx_5noc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="tcsx_5noc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:book-open-16" {...props}></Icon>
