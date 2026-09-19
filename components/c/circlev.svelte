<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vipa3vb_w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="vipa3vb_w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:circlev" {...props}></Icon>
