<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ok-0j3bcs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ok-0j3bcs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="basil:checked-box-solid" {...props}></Icon>
