<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/miqof0biz.css';
import '../../css/p/p-rfurwvz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":12};
const content = `<path class="miqof0biz"/><path class="p-rfurwvz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="formkit:rewind" {...props}></Icon>
