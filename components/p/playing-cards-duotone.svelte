<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/z/zao9-4fdy.css';
import '../../css/x/xxxy15abp.css';
import '../../css/t/te5e841nv.css';
import '../../css/h/hg6om7bpf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="zao9-4fdy"/><path class="xxxy15abp"/><path class="te5e841nv"/><path class="hg6om7bpf"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:playing-cards-duotone" {...props}></Icon>
