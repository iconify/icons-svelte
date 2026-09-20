<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/ty__8pbjv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ty__8pbjv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:hackclub" {...props}></Icon>
