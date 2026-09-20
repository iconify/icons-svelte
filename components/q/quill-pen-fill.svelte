<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cdu937bja.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cdu937bja"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:quill-pen-fill" {...props}></Icon>
