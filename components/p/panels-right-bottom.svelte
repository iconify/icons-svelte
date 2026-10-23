<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v0ucx7bbw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="v0ucx7bbw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:panels-right-bottom" {...props}></Icon>
