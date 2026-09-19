<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/ro7j6o5qa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ro7j6o5qa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:arrow-elbow-right-up" {...props}></Icon>
