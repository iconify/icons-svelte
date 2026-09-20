<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ibylg52rv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="ibylg52rv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:bluetooth-16" {...props}></Icon>
