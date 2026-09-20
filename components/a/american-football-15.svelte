<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mj25bjbhv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="mj25bjbhv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="maki:american-football-15" {...props}></Icon>
