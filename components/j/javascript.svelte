<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cnk53dbzv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cnk53dbzv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:javascript" {...props}></Icon>
