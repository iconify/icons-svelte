<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o75vn0b-t.css';
import '../../css/k/kbzcbrwur.css';
import '../../css/w/wukahqb_c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="o75vn0b-t"/><path class="kbzcbrwur"/><path clip-rule="evenodd" class="wukahqb_c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:paste-24" {...props}></Icon>
