<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/ca_p1nbxt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ca_p1nbxt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:clear-all-fill" {...props}></Icon>
