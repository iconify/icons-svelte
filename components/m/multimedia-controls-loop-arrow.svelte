<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b91wmnvdz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="b91wmnvdz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-freehand-color:multimedia-controls-loop-arrow" {...props}></Icon>
