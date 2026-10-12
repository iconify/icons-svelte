<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hpyifib8k.css';
import '../../css/t/tzudepndl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hpyifib8k"/><path class="tzudepndl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:phone-forwarded-filled" {...props}></Icon>
