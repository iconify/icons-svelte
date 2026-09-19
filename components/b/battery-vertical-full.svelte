<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qr66j6b6j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="qr66j6b6j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:battery-vertical-full" {...props}></Icon>
