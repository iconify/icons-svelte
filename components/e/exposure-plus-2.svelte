<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kcxd1c7pw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kcxd1c7pw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:exposure-plus-2" {...props}></Icon>
