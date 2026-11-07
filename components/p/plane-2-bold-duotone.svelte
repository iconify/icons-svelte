<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b4suqz_5f.css';
import '../../css/m/mrdfzse1o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="b4suqz_5f"/><path class="mrdfzse1o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:plane-2-bold-duotone" {...props}></Icon>
