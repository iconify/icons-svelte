<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ycs9h4bkb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="ycs9h4bkb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-regular:face-dizzy" {...props}></Icon>
