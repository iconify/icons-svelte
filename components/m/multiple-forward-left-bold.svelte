<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/huxj-vhdc.css';
import '../../css/g/gqrwazmcy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="huxj-vhdc"/><path clip-rule="evenodd" class="gqrwazmcy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:multiple-forward-left-bold" {...props}></Icon>
