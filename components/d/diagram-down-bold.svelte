<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/umqx0z94l.css';
import '../../css/t/t978a44vc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="umqx0z94l"/><path class="t978a44vc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:diagram-down-bold" {...props}></Icon>
