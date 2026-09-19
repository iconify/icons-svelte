<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x3az_8srk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":547,"height":762};
const content = `<path class="x3az_8srk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ls:a-upper-case" {...props}></Icon>
