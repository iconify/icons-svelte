<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jzh1ikioz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="jzh1ikioz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:person-squatting" {...props}></Icon>
