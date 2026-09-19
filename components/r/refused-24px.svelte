<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q4rf0mbdo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="q4rf0mbdo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:refused-24px" {...props}></Icon>
