<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zjah4orxl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="zjah4orxl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:arrow-elbow-left-down" {...props}></Icon>
