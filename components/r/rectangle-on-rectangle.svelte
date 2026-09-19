<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sfrn8jbhb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="sfrn8jbhb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:rectangle-on-rectangle" {...props}></Icon>
