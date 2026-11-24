<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ao_dv4bpw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ao_dv4bpw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:play-off-filled" {...props}></Icon>
