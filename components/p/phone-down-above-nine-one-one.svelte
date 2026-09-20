<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kj-q25bgf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="kj-q25bgf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:phone-down-above-nine-one-one" {...props}></Icon>
