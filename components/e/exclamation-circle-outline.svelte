<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gfjex6bnk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="gfjex6bnk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:exclamation-circle-outline" {...props}></Icon>
