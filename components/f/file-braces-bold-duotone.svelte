<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jav_zgbsf.css';
import '../../css/l/l3981gogh.css';
import '../../css/u/ubn_7xb7s.css';
import '../../css/o/oj6gwrmjs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jav_zgbsf"/><path class="l3981gogh"/><path class="ubn_7xb7s"/><path clip-rule="evenodd" class="oj6gwrmjs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:file-braces-bold-duotone" {...props}></Icon>
