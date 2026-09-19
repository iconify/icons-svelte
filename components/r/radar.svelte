<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yhj_6240a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="yhj_6240a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:radar" {...props}></Icon>
