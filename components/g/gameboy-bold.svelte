<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gqb4xlb7r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="gqb4xlb7r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:gameboy-bold" {...props}></Icon>
