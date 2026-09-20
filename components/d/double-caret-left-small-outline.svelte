<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fw25wvpgw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="fw25wvpgw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:double-caret-left-small-outline" {...props}></Icon>
