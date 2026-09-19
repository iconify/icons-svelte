<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bpv-s6b0z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="bpv-s6b0z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:alarm-snooze" {...props}></Icon>
