<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hkxht-b5w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="hkxht-b5w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cib:hatena-bookmark" {...props}></Icon>
