<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iin1szbru.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="iin1szbru"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:phone-call" {...props}></Icon>
