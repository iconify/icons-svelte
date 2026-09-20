<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h14_rhpgn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="h14_rhpgn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:database-16" {...props}></Icon>
