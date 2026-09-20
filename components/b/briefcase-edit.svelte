<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/txvyk-sgs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="txvyk-sgs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:briefcase-edit" {...props}></Icon>
