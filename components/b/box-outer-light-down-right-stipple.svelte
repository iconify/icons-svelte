<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pw_or0bfk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":22,"height":22};
const content = `<path class="pw_or0bfk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="memory:box-outer-light-down-right-stipple" {...props}></Icon>
