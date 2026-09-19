<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rc02xp00d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="rc02xp00d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:arrow-up-left-arrow-down-right" {...props}></Icon>
