<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hcye7x86p.css';
import '../../css/x/xwx0momul.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hcye7x86p"/><path class="xwx0momul"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixel:face-thinking" {...props}></Icon>
