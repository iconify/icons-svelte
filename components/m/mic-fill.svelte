<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/ggyqufb9a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="ggyqufb9a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:mic-fill" {...props}></Icon>
