<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ik_1hnawp.css';
import '../../css/f/fhqkw7bht.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ik_1hnawp"/><path class="fhqkw7bht"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:link-round-bold-duotone" {...props}></Icon>
