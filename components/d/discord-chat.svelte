<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k1j0aebsi.css';
import '../../css/s/sq9kvubup.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k1j0aebsi"/><path class="sq9kvubup"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:discord-chat" {...props}></Icon>
