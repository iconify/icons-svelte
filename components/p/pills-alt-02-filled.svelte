<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e32pzmbzj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="e32pzmbzj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:pills-alt-02-filled" {...props}></Icon>
