<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ifwq_acdd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ifwq_acdd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lets-icons:favorite-duotone" {...props}></Icon>
