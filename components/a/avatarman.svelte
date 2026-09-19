<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v9mpdcwxa.css';
import '../../css/y/yh9pzinki.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":13,"height":16};
const content = `<path class="v9mpdcwxa"/><path class="yh9pzinki"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="formkit:avatarman" {...props}></Icon>
