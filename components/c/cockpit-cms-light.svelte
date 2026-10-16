<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ie4p76ois.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":310,"height":310};
const content = `<path class="ie4p76ois"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:cockpit-cms-light" {...props}></Icon>
