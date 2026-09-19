<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jgu-rub7m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":582,"height":674};
const content = `<path class="jgu-rub7m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ls:myspace" {...props}></Icon>
