<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nm2cgjbbr.css';
import '../../css/v/vh0_98nmz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nm2cgjbbr"/><path class="vh0_98nmz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:arrow-up-from-line-bold" {...props}></Icon>
