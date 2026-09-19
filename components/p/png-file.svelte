<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dedd0_bzk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="dedd0_bzk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:png-file" {...props}></Icon>
