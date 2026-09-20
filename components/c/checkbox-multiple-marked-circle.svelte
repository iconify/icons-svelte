<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nskwcxbed.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nskwcxbed"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:checkbox-multiple-marked-circle" {...props}></Icon>
