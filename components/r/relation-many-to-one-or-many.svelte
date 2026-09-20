<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h7-blbuve.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h7-blbuve"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:relation-many-to-one-or-many" {...props}></Icon>
