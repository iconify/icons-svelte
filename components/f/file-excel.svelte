<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/ds2udfbbe.css';
import '../../css/g/gr02mac6c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ds2udfbbe"/><path class="gr02mac6c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="prime:file-excel" {...props}></Icon>
