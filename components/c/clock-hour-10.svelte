<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wrbc_pbor.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wrbc_pbor"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:clock-hour-10" {...props}></Icon>
