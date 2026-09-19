<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/orxitfbis.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":255,"height":754};
const content = `<path class="orxitfbis"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ls:f" {...props}></Icon>
