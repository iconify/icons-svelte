<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h12_74eoa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h12_74eoa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:glasses-2-fill" {...props}></Icon>
