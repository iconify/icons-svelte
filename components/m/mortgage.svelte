<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rb2kd0rju.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="rb2kd0rju"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:mortgage" {...props}></Icon>
