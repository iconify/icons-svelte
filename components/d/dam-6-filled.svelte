<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ejyr96b-o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ejyr96b-o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:dam-6-filled" {...props}></Icon>
