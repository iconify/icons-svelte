<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/irrpp75oa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="irrpp75oa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:babel" {...props}></Icon>
