<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k3c2rj_zs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k3c2rj_zs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:arrow-u-turn-left-sharp-fill" {...props}></Icon>
