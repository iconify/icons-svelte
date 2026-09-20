<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/axfk7i5wf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="axfk7i5wf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:cloud" {...props}></Icon>
