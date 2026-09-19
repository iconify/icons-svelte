<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t0tu5dsyz.css';
import '../../css/i/if95wl24z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t0tu5dsyz"/><path class="if95wl24z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:microphone-slash-filled" {...props}></Icon>
