<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h4ovl2bdw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="h4ovl2bdw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:ag-ui" {...props}></Icon>
