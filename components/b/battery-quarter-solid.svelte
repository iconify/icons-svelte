<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j9-n_p_wf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="j9-n_p_wf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="basil:battery-quarter-solid" {...props}></Icon>
