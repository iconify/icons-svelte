<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kwgshwb8o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kwgshwb8o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:dapr" {...props}></Icon>
