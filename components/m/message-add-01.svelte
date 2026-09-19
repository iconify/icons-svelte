<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z3k13gdbv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z3k13gdbv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:message-add-01" {...props}></Icon>
