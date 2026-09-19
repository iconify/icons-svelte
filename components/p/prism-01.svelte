<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fnqnvub1c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fnqnvub1c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:prism-01" {...props}></Icon>
