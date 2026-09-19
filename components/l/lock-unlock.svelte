<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ijigewbbk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ijigewbbk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gg:lock-unlock" {...props}></Icon>
