<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o05uwt_pv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o05uwt_pv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="feather:minimize-2" {...props}></Icon>
