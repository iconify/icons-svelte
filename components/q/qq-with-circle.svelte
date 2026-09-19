<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/owx5tpc2l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="owx5tpc2l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="entypo-social:qq-with-circle" {...props}></Icon>
