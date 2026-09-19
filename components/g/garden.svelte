<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mu_l0pbck.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mu_l0pbck"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:garden" {...props}></Icon>
