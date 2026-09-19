<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dyp2mwbic.css';
import '../../css/b/bfjbko1wp.css';
import '../../css/i/i4ytxgbzl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="dyp2mwbic"/><path class="bfjbko1wp"/><path class="i4ytxgbzl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flat-color-icons:data-configuration" {...props}></Icon>
