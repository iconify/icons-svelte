<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t_2ehyb_k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t_2ehyb_k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:redhat" {...props}></Icon>
