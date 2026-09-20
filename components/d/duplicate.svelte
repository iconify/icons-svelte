<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a61m6fb_v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="a61m6fb_v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pajamas:duplicate" {...props}></Icon>
