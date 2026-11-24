<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dyk60-btd.css';
import '../../css/j/jcbj2xbrn.css';
import '../../css/x/xe8-vm0oy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dyk60-btd"/><path class="jcbj2xbrn"/><path class="xe8-vm0oy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:cloud-sync-filled" {...props}></Icon>
