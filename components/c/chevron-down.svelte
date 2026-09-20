<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/npjel3gno.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="npjel3gno"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:chevron-down" {...props}></Icon>
