<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ocj5ybcgv.css';
import '../../css/f/fhz4q76lt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ocj5ybcgv"/><path class="fhz4q76lt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:allowances-no-photos-bold" {...props}></Icon>
