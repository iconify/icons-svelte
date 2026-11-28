<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tkag413ll.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tkag413ll"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:message-square-edit" {...props}></Icon>
