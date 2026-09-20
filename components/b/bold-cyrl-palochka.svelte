<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tt6-dubor.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="tt6-dubor"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ooui:bold-cyrl-palochka" {...props}></Icon>
