<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s412b-n-e.css';
import '../../css/m/mb0wncc3g.css';
import '../../css/a/abe0tyb8t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s412b-n-e"/><path class="mb0wncc3g"/><path class="abe0tyb8t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:random-line" {...props}></Icon>
