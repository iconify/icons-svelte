<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r_o7jfard.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="r_o7jfard"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:reply" {...props}></Icon>
