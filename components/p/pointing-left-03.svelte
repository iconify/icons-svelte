<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n_ah_3bjy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="n_ah_3bjy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:pointing-left-03" {...props}></Icon>
