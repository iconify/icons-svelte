<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ob3i90--v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ob3i90--v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:clock-three" {...props}></Icon>
