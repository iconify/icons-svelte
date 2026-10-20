<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fzs5177np.css';
import '../../css/l/lgqt567fo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="fzs5177np"/><path class="lgqt567fo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:message-sparkle-20" {...props}></Icon>
