<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nih4kjbsf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nih4kjbsf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons-outline:gift-top" {...props}></Icon>
