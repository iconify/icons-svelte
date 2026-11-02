<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lrttn8byy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lrttn8byy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:beef-off-fill" {...props}></Icon>
