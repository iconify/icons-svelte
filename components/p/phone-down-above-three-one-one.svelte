<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kkser5_na.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="kkser5_na"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:phone-down-above-three-one-one" {...props}></Icon>
