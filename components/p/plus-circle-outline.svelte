<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sih672bgv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sih672bgv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ci:plus-circle-outline" {...props}></Icon>
