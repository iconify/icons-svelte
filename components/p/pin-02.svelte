<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oj36n2brk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="oj36n2brk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:pin-02" {...props}></Icon>
