<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xly2t3apw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="xly2t3apw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:plain-text" {...props}></Icon>
