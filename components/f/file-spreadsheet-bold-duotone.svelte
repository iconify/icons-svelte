<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oj6gwrmjs.css';
import '../../css/i/ixw1cy8fb.css';
import '../../css/g/g502-xb2c.css';
import '../../css/m/mdomo9bqv.css';
import '../../css/a/a04zgy3zm.css';
import '../../css/x/x4f46-b2l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="oj6gwrmjs"/><path class="ixw1cy8fb"/><path class="g502-xb2c"/><path class="mdomo9bqv"/><path class="a04zgy3zm"/><path class="x4f46-b2l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:file-spreadsheet-bold-duotone" {...props}></Icon>
