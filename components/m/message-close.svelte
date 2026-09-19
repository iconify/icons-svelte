<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qr5qhybdn.css';
import '../../css/f/ftg34obra.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qr5qhybdn"/><path class="ftg34obra"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ci:message-close" {...props}></Icon>
