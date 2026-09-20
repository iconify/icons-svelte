<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bru_blbiw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bru_blbiw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:audio" {...props}></Icon>
