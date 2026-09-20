<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/ja_hni21a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ja_hni21a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:opensuse-leap-light" {...props}></Icon>
