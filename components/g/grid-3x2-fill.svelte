<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r9zwy09dw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="r9zwy09dw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:grid-3x2-fill" {...props}></Icon>
