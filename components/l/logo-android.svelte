<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/weah1dbwi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="weah1dbwi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:logo-android" {...props}></Icon>
