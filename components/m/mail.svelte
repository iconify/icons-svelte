<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v3yk7pb8w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":100,"height":100};
const content = `<path class="v3yk7pb8w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="foundation:mail" {...props}></Icon>
