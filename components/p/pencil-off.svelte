<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/so5y9pc7i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="so5y9pc7i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:pencil-off" {...props}></Icon>
