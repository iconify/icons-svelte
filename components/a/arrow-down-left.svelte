<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/ckgms1beq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ckgms1beq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="meteor-icons:arrow-down-left" {...props}></Icon>
