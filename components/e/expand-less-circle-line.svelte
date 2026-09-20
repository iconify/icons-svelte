<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jykrjdbni.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jykrjdbni"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:expand-less-circle-line" {...props}></Icon>
