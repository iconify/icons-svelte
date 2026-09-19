<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h40om-n7w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h40om-n7w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gridicons:briefcase" {...props}></Icon>
