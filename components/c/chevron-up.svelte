<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mk-59o6jn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="mk-59o6jn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pajamas:chevron-up" {...props}></Icon>
