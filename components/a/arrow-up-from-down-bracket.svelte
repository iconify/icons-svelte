<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h37jq-dsh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="h37jq-dsh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:arrow-up-from-down-bracket" {...props}></Icon>
