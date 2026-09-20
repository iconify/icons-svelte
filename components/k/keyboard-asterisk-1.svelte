<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dvm6k-5fl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="dvm6k-5fl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-freehand-color:keyboard-asterisk-1" {...props}></Icon>
