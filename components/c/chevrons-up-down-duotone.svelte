<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iqpgrsbwp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="iqpgrsbwp primary"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:chevrons-up-down-duotone" {...props}></Icon>
