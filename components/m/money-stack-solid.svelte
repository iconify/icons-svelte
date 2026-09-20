<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gblqb-qvt.css';
import '../../css/x/xaa7x4xbn.css';
import '../../css/x/x9866xb-a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="gblqb-qvt"/><path clip-rule="evenodd" class="xaa7x4xbn"/><path class="x9866xb-a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:money-stack-solid" {...props}></Icon>
