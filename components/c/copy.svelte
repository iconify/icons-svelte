<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sbj_rt5nz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sbj_rt5nz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="grommet-icons:copy" {...props}></Icon>
