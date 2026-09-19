<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iwlh7mskr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="iwlh7mskr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxl:medium-old" {...props}></Icon>
