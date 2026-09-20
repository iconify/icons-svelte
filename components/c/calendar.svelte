<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r2c34gbpd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":26,"height":26};
const content = `<path class="r2c34gbpd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="wpf:calendar" {...props}></Icon>
