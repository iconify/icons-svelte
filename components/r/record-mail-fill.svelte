<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tvpw6c4jp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tvpw6c4jp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:record-mail-fill" {...props}></Icon>
