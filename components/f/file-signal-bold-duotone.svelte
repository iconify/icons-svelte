<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oj6gwrmjs.css';
import '../../css/e/epxpc5bbp.css';
import '../../css/n/ng2t0it8x.css';
import '../../css/f/fmnpkbl0c.css';
import '../../css/x/x4f46-b2l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="oj6gwrmjs"/><path class="epxpc5bbp"/><path class="ng2t0it8x"/><path clip-rule="evenodd" class="fmnpkbl0c"/><path class="x4f46-b2l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:file-signal-bold-duotone" {...props}></Icon>
