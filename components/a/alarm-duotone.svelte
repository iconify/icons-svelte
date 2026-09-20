<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hu0krdbdg.css';
import '../../css/g/gcnxx2xsc.css';
import '../../css/z/zopjch_2q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hu0krdbdg"><path class="gcnxx2xsc"/><circle class="zopjch_2q"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lets-icons:alarm-duotone" {...props}></Icon>
