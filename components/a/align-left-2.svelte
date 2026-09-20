<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s1tt42brv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s1tt42brv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:align-left-2" {...props}></Icon>
