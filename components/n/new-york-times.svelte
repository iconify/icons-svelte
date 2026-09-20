<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hsh0-jb5d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hsh0-jb5d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:new-york-times" {...props}></Icon>
