<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/peqpa-bko.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24,"left":-2,"top":-5};
const content = `<path class="peqpa-bko"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="jam:cloud-f" {...props}></Icon>
