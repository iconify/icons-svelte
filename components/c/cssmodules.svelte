<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nbr1m2bpj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nbr1m2bpj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:cssmodules" {...props}></Icon>
