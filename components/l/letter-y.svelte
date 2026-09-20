<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g40e2t11v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g40e2t11v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:letter-y" {...props}></Icon>
