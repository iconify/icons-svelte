<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mu_n3ebem.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mu_n3ebem"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:arrow-button-right-1" {...props}></Icon>
