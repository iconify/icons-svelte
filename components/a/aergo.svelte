<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xi609bcuk.css';
import '../../css/s/s-xq_4b7p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xi609bcuk"/><path class="s-xq_4b7p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:aergo" {...props}></Icon>
