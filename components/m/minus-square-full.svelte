<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gjj4o5bfd.css';
import '../../css/z/zuoex-dnf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gjj4o5bfd"/><path class="zuoex-dnf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uim:minus-square-full" {...props}></Icon>
