<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tznh8nfow.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tznh8nfow"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lets-icons:done" {...props}></Icon>
