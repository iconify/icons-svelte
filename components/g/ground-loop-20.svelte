<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v-tex-1tc.css';
import '../../css/v/vzrht_bih.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="v-tex-1tc"/><path class="vzrht_bih"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:ground-loop-20" {...props}></Icon>
