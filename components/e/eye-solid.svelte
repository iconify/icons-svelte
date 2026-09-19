<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gxao0zblb.css';
import '../../css/m/mdvlj20nw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gxao0zblb"/><path clip-rule="evenodd" class="mdvlj20nw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="basil:eye-solid" {...props}></Icon>
