<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wr2exacnp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="wr2exacnp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:building-fill" {...props}></Icon>
