<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/m/mbpy0ib_u.css';
import '../../css/d/doei1kbpv.css';
import '../../css/m/my85rfpjo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path clip-rule="evenodd" class="mbpy0ib_u"/><path class="doei1kbpv"/><path clip-rule="evenodd" class="my85rfpjo"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp-color:play-list-1-flat" {...props}></Icon>
