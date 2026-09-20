<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/srkv66j6m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="srkv66j6m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:mint" {...props}></Icon>
