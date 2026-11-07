<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cl66i7bqg.css';
import '../../css/a/anq4ponik.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<circle class="cl66i7bqg"/><path class="anq4ponik"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:magnifier-bold-duotone" {...props}></Icon>
