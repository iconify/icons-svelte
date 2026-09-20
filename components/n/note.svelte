<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cea-4hbdw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cea-4hbdw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:note" {...props}></Icon>
