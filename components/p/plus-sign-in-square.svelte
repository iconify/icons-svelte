<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/varwkcb3v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="varwkcb3v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="at-icons:plus-sign-in-square" {...props}></Icon>
