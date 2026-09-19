<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o46uosa4l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="o46uosa4l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:hospitalized-outline-24px" {...props}></Icon>
