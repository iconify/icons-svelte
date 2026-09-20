<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ie1qbx9oa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ie1qbx9oa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:folders-fill" {...props}></Icon>
