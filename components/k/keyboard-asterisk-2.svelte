<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vik2i1kjg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="vik2i1kjg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-freehand-color:keyboard-asterisk-2" {...props}></Icon>
