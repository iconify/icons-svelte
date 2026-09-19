<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ee_489afo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ee_489afo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gcp:cloud-for-marketing" {...props}></Icon>
