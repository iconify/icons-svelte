<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y9wi6kl_c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="y9wi6kl_c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:number-17-small" {...props}></Icon>
