<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mya2ylbms.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="mya2ylbms"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:arrows-up" {...props}></Icon>
