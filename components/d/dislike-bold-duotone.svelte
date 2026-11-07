<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wo0q5ob3i.css';
import '../../css/v/vj8wfhhvy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wo0q5ob3i"/><path clip-rule="evenodd" class="vj8wfhhvy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:dislike-bold-duotone" {...props}></Icon>
