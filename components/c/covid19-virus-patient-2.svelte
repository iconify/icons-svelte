<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d4tiu56qm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d4tiu56qm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="covid:covid19-virus-patient-2" {...props}></Icon>
