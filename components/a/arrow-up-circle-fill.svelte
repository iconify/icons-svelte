<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x6u424bun.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="x6u424bun"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:arrow-up-circle-fill" {...props}></Icon>
