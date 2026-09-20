<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jpb2fcc-i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="jpb2fcc-i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:multiselect-fill" {...props}></Icon>
