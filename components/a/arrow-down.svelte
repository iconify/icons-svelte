<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iwzdfkbpj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="iwzdfkbpj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:arrow-down" {...props}></Icon>
