<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eaw0jcbdl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="eaw0jcbdl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:presentation-edit" {...props}></Icon>
