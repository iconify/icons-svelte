<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uqeo4nzcu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="uqeo4nzcu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:key-shift-16" {...props}></Icon>
