<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/ljycq4b6e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="ljycq4b6e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:person-3" {...props}></Icon>
