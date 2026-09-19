<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v-tor2b0m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="v-tor2b0m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:doc-on-doc" {...props}></Icon>
