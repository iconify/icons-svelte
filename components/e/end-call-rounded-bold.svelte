<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gnokzacxm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gnokzacxm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:end-call-rounded-bold" {...props}></Icon>
