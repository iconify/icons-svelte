<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/polv-0les.css';
import '../../css/f/fsw0aeb5r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="polv-0les"/><path class="fsw0aeb5r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:last-updates-solid" {...props}></Icon>
