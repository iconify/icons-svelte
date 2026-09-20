<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dlrq9nb_a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dlrq9nb_a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:adblock" {...props}></Icon>
