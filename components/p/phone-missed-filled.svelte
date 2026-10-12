<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hpyifib8k.css';
import '../../css/h/hj55octgf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hpyifib8k"/><path class="hj55octgf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:phone-missed-filled" {...props}></Icon>
