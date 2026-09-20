<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ifei00vdh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ifei00vdh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:estate" {...props}></Icon>
