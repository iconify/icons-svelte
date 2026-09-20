<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x9r9llbfe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="x9r9llbfe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-freehand-color:remove-subtract-sign-bold" {...props}></Icon>
