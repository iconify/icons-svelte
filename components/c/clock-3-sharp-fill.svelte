<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q74n_kb-t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="q74n_kb-t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:clock-3-sharp-fill" {...props}></Icon>
