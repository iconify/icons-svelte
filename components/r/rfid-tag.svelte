<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x4ssq09rn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":26,"height":26};
const content = `<path class="x4ssq09rn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="wpf:rfid-tag" {...props}></Icon>
