<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zmh4fhb6b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zmh4fhb6b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:radiology-scan-doctor-bold" {...props}></Icon>
