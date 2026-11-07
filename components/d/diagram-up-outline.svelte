<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/umqx0z94l.css';
import '../../css/p/pru_4-bvp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="umqx0z94l"/><path class="pru_4-bvp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:diagram-up-outline" {...props}></Icon>
