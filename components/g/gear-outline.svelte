<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z82u_nr1i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="z82u_nr1i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bitcoin-icons:gear-outline" {...props}></Icon>
