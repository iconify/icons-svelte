<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nb6hxoxix.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":22,"height":19};
const content = `<path class="nb6hxoxix"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:activepieces" {...props}></Icon>
