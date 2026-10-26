<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h2zfnvgut.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h2zfnvgut"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:resilient-and-migration-sensitive-health-system-24px" {...props}></Icon>
