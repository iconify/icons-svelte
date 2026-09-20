<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kqx49sbfq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kqx49sbfq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:circle-swiss-franc-sharp-fill" {...props}></Icon>
