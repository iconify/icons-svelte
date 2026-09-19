<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rbsibt3cj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rbsibt3cj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:radar" {...props}></Icon>
