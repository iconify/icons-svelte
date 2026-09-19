<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y5-5xebiw.css';
import '../../css/z/z7ybbhltq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="y5-5xebiw"/><path class="z7ybbhltq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:arrow-in-left-circle-half-filled" {...props}></Icon>
