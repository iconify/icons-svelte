<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rosrm6b3v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rosrm6b3v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:email-open" {...props}></Icon>
