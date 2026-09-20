<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hw5gyubsx.css';
import '../../css/j/jjcq2bbuw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hw5gyubsx"/><path class="jjcq2bbuw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:map-chat-filled" {...props}></Icon>
