<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dol_h130o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="dol_h130o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp-color:prescription-pills-drugs-healthcare-flat" {...props}></Icon>
