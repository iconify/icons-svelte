<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fq_fqub5c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fq_fqub5c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:emotion-normal-fill" {...props}></Icon>
